<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnvz6ub2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jnvz6ub2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:gear" /></template>
