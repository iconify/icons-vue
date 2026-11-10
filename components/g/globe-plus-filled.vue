<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw-wcrb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw-wcrb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-plus-filled" /></template>
