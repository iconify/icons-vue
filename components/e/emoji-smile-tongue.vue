<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xineib3hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xineib3hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:emoji-smile-tongue" /></template>
