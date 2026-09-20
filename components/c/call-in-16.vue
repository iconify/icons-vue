<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wisis3x7u.css';
import '../../css/m/mprc9wbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wisis3x7u"/><path class="mprc9wbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:call-in-16" /></template>
