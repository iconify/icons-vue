<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_h9oache.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="b_h9oache"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:circle-11" /></template>
