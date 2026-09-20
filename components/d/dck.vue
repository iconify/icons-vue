<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl5fu-xjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl5fu-xjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dck" /></template>
