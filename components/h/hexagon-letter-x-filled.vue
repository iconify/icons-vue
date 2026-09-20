<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqfzzh-5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqfzzh-5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-x-filled" /></template>
