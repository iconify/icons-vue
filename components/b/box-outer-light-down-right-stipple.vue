<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw_or0bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pw_or0bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-down-right-stipple" /></template>
