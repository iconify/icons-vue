<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvf_dk-1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvf_dk-1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cylinder-2-fill" /></template>
