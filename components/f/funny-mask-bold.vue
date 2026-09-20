<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqmb-4fki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqmb-4fki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:funny-mask-bold" /></template>
