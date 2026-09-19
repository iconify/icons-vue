<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5m55j0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zv5m55j0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingtwo" /></template>
