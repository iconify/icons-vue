<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwtuk-ylk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwtuk-ylk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adobelightroom" /></template>
