<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxd1sc-xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxd1sc-xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-check" /></template>
