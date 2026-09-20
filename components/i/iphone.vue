<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvu2o1bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qvu2o1bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:iphone" /></template>
