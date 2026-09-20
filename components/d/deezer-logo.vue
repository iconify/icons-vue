<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od-418bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od-418bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:deezer-logo" /></template>
