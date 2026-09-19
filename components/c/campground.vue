<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw3q3-91j.css';
import '../../css/z/zo8llxvbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw3q3-91j duoicon-secondary-layer"/><path class="duoicon-primary-layer zo8llxvbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:campground" /></template>
