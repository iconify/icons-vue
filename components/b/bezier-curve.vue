<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzlm72b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="pzlm72b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bezier-curve" /></template>
