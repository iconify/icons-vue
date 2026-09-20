<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj2n_6b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj2n_6b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:android-head" /></template>
