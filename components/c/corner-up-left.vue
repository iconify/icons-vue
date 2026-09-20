<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biybgwbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biybgwbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:corner-up-left" /></template>
