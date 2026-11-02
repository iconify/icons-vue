<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6dr5jbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6dr5jbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-off-fill" /></template>
