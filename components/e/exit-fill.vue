<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqfg2e1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjqfg2e1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exit-fill" /></template>
