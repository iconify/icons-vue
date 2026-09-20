<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm1ygvb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm1ygvb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:carousel-horizontal" /></template>
