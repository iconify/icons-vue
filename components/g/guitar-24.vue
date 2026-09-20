<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm_h54lxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm_h54lxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-24" /></template>
