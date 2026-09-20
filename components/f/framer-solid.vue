<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jncj_it4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jncj_it4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:framer-solid" /></template>
