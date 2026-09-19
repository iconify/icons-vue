<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adhf5bblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adhf5bblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-circle-quarter" /></template>
