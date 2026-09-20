<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud7xhmbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud7xhmbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:link-one" /></template>
