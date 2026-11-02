<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yze8-eekk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yze8-eekk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-check-fill" /></template>
