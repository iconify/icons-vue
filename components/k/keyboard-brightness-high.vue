<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9-1wccab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9-1wccab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:keyboard-brightness-high" /></template>
