<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq34y74ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bq34y74ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hadoop" /></template>
