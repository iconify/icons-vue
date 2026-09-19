<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyk46-7ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jyk46-7ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:block-four" /></template>
