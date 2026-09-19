<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_wi8bcoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="u_wi8bcoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alignleft" /></template>
