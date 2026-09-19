<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exu4375zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exu4375zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:headphone-alt" /></template>
