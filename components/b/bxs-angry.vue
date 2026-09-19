<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg14v6-br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg14v6-br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-angry" /></template>
