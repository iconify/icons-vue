<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckhx8tb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ckhx8tb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:comb" /></template>
