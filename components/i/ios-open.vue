<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb8ysxktc.css';
import '../../css/r/r6esm02yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lb8ysxktc"/><path class="r6esm02yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-open" /></template>
