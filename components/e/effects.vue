<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw1e9n7xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rw1e9n7xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:effects" /></template>
