<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syay5usio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syay5usio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:ai-operator" /></template>
