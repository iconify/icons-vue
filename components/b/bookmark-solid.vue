<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjfc7kb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pjfc7kb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bookmark-solid" /></template>
