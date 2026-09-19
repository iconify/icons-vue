<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7bk3wbqk.css';
import '../../css/r/r7lg6bmas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o7bk3wbqk"/><path class="r7lg6bmas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:back" /></template>
