<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kul0447wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kul0447wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-none" /></template>
