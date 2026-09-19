<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c46figbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c46figbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlebackwardempty" /></template>
