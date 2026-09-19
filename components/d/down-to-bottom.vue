<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scn8kmb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="scn8kmb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:down-to-bottom" /></template>
