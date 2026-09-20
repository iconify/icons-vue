<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzx0mkbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzx0mkbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-k" /></template>
