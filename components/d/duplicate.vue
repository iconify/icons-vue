<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3ipj9r7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u3ipj9r7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:duplicate" /></template>
