<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x59z4hb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x59z4hb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brightness-alt-high" /></template>
