<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmv3p70cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmv3p70cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-right-solid" /></template>
