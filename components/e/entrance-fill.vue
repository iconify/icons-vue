<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb60v9_9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb60v9_9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:entrance-fill" /></template>
