<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxg2k8bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg2k8bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:battery-charging" /></template>
