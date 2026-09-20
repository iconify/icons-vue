<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0rcjl2mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0rcjl2mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-mark-line" /></template>
