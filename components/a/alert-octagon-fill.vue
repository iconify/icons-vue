<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoj-6vd9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xoj-6vd9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-octagon-fill" /></template>
