<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klde9sz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klde9sz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:delete" /></template>
