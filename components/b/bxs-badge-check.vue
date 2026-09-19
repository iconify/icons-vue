<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxs5jcbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxs5jcbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-badge-check" /></template>
