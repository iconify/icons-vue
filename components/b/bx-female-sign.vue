<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gldgrx7rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gldgrx7rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-female-sign" /></template>
