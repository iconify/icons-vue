<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6qo4yo6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="m6qo4yo6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chess-bishop" /></template>
