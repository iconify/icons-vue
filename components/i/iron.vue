<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0kgj6bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r0kgj6bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:iron" /></template>
