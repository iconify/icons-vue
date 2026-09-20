<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgn242ovo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgn242ovo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:buildings3" /></template>
