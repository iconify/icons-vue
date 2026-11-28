<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jga97rkuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jga97rkuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:italic" /></template>
