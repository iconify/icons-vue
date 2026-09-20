<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0jrkyu8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y0jrkyu8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-alt-outline" /></template>
