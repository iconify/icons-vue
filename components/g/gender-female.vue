<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv9y25q_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv9y25q_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gender-female" /></template>
