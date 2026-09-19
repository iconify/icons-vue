<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulfpgv-qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulfpgv-qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:invader" /></template>
