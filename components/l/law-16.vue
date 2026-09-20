<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2n_s1h7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l2n_s1h7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:law-16" /></template>
