<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh0tirbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hh0tirbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:house-filled" /></template>
