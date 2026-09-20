<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djzvpbbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="djzvpbbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:face-with-tongue-out-in-circle" /></template>
