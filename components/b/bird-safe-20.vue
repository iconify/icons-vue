<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoimw9qqn.css';
import '../../css/j/jgct6lokd.css';
import '../../css/c/c_j3vh1fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xoimw9qqn"/><path class="jgct6lokd"/><path class="c_j3vh1fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bird-safe-20" /></template>
