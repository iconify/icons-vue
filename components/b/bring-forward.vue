<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwgm37udc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwgm37udc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bring-forward" /></template>
