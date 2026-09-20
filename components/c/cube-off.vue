<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0myofk9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0myofk9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cube-off" /></template>
