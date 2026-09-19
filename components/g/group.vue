<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_4qcfbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_4qcfbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:group" /></template>
