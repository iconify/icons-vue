<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnvuzvbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnvuzvbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:grid-big" /></template>
