<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b51trz_uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b51trz_uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fingerprint-line" /></template>
