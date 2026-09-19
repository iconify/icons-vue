<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xulhkp85g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="xulhkp85g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:icecreamthree" /></template>
