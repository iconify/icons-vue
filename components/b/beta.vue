<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0nnzt4lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0nnzt4lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:beta" /></template>
