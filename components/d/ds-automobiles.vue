<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpvie97gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpvie97gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ds-automobiles" /></template>
