<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq4cngnfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq4cngnfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flip-vertical" /></template>
