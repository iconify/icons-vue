<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro6wwmbtu.css';
import '../../css/s/sxbjysb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="ro6wwmbtu"/><path class="sxbjysb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bumpsight" /></template>
