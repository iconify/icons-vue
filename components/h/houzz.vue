<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uym9oabze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":24};
const content = `<path class="uym9oabze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:houzz" /></template>
