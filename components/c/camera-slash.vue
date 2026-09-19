<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7w50vvhh.css';
import '../../css/r/rgxtolv2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7w50vvhh"/><path class="rgxtolv2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-slash" /></template>
