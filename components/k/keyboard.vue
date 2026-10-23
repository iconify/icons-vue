<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt-hzv5tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt-hzv5tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:keyboard" /></template>
