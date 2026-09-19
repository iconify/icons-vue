<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n48inlb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n48inlb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-hogvind" /></template>
