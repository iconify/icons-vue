<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkm_1v9vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkm_1v9vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-up-circle-solid" /></template>
