<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5dk1gb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5dk1gb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:creative-commons" /></template>
