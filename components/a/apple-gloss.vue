<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp1cej1ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp1cej1ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:apple-gloss" /></template>
