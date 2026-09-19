<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o62692bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":760,"height":1000};
const content = `<path class="o62692bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:doc" /></template>
