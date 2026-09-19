<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r99neac-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r99neac-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:book-alt" /></template>
