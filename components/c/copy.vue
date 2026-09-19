<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzm83z9bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzm83z9bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:copy" /></template>
