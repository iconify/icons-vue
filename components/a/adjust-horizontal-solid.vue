<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bczujtj-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bczujtj-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:adjust-horizontal-solid" /></template>
