<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0apn84ov.css';
import '../../css/v/vku8ojb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0apn84ov"/><path class="vku8ojb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-down-square" /></template>
