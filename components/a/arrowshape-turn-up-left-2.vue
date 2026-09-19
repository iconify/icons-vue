<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5e7_6j1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b5e7_6j1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowshape-turn-up-left-2" /></template>
