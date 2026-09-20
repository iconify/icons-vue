<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb1gmnbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb1gmnbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-number-4-filled" /></template>
