<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6lc_ebxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o6lc_ebxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emojismile" /></template>
