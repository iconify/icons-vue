<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ix1vbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ix1vbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-share" /></template>
