<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnzv0wjzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jnzv0wjzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:fireworks" /></template>
