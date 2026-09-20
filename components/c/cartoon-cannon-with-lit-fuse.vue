<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe47tqu_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oe47tqu_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cartoon-cannon-with-lit-fuse" /></template>
