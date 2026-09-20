<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbl1zguft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbl1zguft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up" /></template>
