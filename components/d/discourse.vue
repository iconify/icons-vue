<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0cr_kblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0cr_kblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:discourse" /></template>
