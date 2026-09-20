<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao6e8934w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao6e8934w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-tugrik" /></template>
