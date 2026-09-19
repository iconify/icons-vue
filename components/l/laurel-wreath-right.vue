<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cufkv7bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cufkv7bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laurel-wreath-right" /></template>
