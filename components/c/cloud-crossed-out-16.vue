<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh4yl5yun.css';
import '../../css/i/i8ocx-9hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rh4yl5yun"/><path class="i8ocx-9hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cloud-crossed-out-16" /></template>
