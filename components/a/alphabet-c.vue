<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkg7nmbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkg7nmbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-c" /></template>
