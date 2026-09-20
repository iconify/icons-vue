<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr1n1y8wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="vr1n1y8wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:flashlight-on-f" /></template>
