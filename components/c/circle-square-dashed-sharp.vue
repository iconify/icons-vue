<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnk_77b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnk_77b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-square-dashed-sharp" /></template>
