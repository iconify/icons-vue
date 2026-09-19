<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2dtwdbdi.css';
import '../../css/s/sec7i9buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2dtwdbdi"/><path class="sec7i9buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-man" /></template>
