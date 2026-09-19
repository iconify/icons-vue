<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzr84ybok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzr84ybok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:grid" /></template>
