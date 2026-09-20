<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jukv0ub1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="jukv0ub1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:caution" /></template>
