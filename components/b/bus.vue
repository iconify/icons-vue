<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be96qhxef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="be96qhxef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bus" /></template>
