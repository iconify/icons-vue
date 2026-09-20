<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw9a3mbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw9a3mbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-minus" /></template>
