<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg_yow_vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg_yow_vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-x-sharp" /></template>
