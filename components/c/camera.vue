<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuzzmybhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="iuzzmybhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:camera" /></template>
