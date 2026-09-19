<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbx1--m4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hbx1--m4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:block-eight" /></template>
