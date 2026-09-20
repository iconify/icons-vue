<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyjt3db7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect vector-effect="non-scaling-stroke" class="oyjt3db7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:home-button" /></template>
