<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud1alzb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":32};
const content = `<path class="ud1alzb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:anchor" /></template>
