<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/excf6z61k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="excf6z61k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cartoon-bomb-with-lit-fuse" /></template>
