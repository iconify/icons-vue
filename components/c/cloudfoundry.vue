<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtdh4fb_d.css';
import '../../css/u/upx6wfzth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtdh4fb_d"/><path class="upx6wfzth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cloudfoundry" /></template>
