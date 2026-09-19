<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om6z7p6bj.css';
import '../../css/d/dy3-7pbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="om6z7p6bj"/><path class="dy3-7pbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ma-1x1" /></template>
