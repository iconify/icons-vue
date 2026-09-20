<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj1rq-cte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj1rq-cte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:accusoft" /></template>
