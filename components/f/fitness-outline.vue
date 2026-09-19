<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_9aq5btt.css';
import '../../css/k/k767t9bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_9aq5btt"/><path class="k767t9bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fitness-outline" /></template>
