<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nihuu_b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="nihuu_b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:id-badge" /></template>
