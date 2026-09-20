<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpibj_16d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpibj_16d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:export3" /></template>
