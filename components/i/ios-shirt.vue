<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxmv_9bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxmv_9bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-shirt" /></template>
