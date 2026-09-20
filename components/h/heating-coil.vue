<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guj_qqblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guj_qqblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heating-coil" /></template>
