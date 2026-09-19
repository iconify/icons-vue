<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk11hsbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk11hsbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bar-bottom" /></template>
