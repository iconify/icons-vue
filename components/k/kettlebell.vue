<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg2p0hbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg2p0hbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:kettlebell" /></template>
