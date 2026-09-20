<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma2b6-b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma2b6-b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-s" /></template>
