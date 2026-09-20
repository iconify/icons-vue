<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2b2__bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2b2__bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-one" /></template>
