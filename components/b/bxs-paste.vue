<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_3eqdman.css';
import '../../css/e/eh1h-1bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_3eqdman"/><path class="eh1h-1bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-paste" /></template>
