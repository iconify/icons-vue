<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgtc5k58y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgtc5k58y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hourglass-filled" /></template>
