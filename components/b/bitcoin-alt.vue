<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4im8ybkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4im8ybkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bitcoin-alt" /></template>
