<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdh68jixy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdh68jixy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dashboard-customize-line" /></template>
