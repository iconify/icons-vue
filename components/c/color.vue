<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5q9z5bbs.css';
import '../../css/v/vvasjdjcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o5q9z5bbs"/><path class="vvasjdjcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:color" /></template>
