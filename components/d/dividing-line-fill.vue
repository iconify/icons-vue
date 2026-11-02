<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idm7ztbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idm7ztbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dividing-line-fill" /></template>
