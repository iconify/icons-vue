<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1_ht_bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1_ht_bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flame-solid" /></template>
