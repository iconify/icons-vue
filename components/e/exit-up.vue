<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0oe0zwr.css';
import '../../css/c/crznqgb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ln0oe0zwr"/><path class="crznqgb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:exit-up" /></template>
