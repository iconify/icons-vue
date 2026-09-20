<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-5x6nayi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":153,"height":42};
const content = `<path clip-rule="evenodd" class="r-5x6nayi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:digikala-persian-text" /></template>
