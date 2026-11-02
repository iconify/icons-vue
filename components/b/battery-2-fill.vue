<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxz9m7bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxz9m7bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-2-fill" /></template>
