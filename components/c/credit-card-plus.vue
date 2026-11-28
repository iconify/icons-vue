<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajgk8lboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajgk8lboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:credit-card-plus" /></template>
