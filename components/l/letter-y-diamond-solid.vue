<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0nhkbdei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0nhkbdei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-y-diamond-solid" /></template>
