<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0dvy_52n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a0dvy_52n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-nine" /></template>
