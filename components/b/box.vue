<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-0kz27_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="b-0kz27_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:box" /></template>
