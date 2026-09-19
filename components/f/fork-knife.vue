<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smi9hnbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smi9hnbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fork-knife" /></template>
