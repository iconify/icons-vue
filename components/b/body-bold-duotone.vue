<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_51kh_lz.css';
import '../../css/i/i6wfjybuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_51kh_lz"/><path class="i6wfjybuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-bold-duotone" /></template>
