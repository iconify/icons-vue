<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrvzomssx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrvzomssx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:full-screen-corner" /></template>
