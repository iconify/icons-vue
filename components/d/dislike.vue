<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2qgdslvz.css';
import '../../css/o/o0xw4kbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r2qgdslvz"/><path class="o0xw4kbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:dislike" /></template>
