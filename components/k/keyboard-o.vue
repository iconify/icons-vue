<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp87_jb1i.css';
import '../../css/p/p8ldtcc9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hp87_jb1i"/><path class="p8ldtcc9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:keyboard-o" /></template>
