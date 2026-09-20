<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt_4qobzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt_4qobzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-iteration" /></template>
