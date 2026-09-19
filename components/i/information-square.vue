<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-mnt58yd.css';
import '../../css/m/mu5v6jmij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b-mnt58yd"/><path class="mu5v6jmij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:information-square" /></template>
