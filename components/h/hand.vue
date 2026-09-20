<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlh79-bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlh79-bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:hand" /></template>
