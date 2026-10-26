<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op-3aacxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="op-3aacxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:chevron-up" /></template>
