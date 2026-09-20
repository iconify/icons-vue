<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdwx1s0ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdwx1s0ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gofx" /></template>
