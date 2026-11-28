<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osx9xfb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osx9xfb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:binary" /></template>
