<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5nwrg5kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5nwrg5kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brief-fill" /></template>
