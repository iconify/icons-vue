<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf0-nebnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pf0-nebnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:down-small-solid" /></template>
