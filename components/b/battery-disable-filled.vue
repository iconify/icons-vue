<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo3ec4yex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo3ec4yex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-disable-filled" /></template>
