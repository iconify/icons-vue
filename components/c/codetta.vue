<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyb13_mva.css';
import '../../css/g/go7uigb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyb13_mva"/><path class="go7uigb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codetta" /></template>
