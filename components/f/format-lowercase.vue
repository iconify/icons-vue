<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8b_nmb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="g8b_nmb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-lowercase" /></template>
