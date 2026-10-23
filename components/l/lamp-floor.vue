<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz5l_acvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz5l_acvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:lamp-floor" /></template>
