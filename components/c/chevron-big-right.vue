<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_isbacso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_isbacso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-big-right" /></template>
