<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpbz6ib3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lpbz6ib3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:control-pause" /></template>
