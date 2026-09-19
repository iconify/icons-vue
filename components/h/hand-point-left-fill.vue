<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsmmhabyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nsmmhabyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hand-point-left-fill" /></template>
