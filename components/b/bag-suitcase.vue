<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1ik_cbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1ik_cbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bag-suitcase" /></template>
