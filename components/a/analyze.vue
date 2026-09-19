<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul57thuxn.css';
import '../../css/f/fq0ccj7nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul57thuxn"/><path class="fq0ccj7nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:analyze" /></template>
