<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q51aqy70n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q51aqy70n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-s-small" /></template>
