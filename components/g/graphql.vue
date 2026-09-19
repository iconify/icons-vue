<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzq6zreob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="lzq6zreob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:graphql" /></template>
