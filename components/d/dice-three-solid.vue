<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrx4xb-sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrx4xb-sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dice-three-solid" /></template>
