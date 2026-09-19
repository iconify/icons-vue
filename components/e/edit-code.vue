<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx9sq5pnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jx9sq5pnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:edit-code" /></template>
