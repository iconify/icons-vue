<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jarn-80ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jarn-80ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docs-collaboration-light" /></template>
