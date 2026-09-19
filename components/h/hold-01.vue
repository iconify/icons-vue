<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq8h0v79p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq8h0v79p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hold-01" /></template>
