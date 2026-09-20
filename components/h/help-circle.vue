<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1ndnv3mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1ndnv3mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:help-circle" /></template>
