<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-6zkcbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-6zkcbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:left" /></template>
