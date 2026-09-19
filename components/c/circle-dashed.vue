<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg8dgjblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg8dgjblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-dashed" /></template>
