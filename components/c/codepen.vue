<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_v783b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="v_v783b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:codepen" /></template>
