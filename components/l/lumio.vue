<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsh3j-hwo.css';
import '../../css/o/oxl9k8wxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xsh3j-hwo"/><path class="oxl9k8wxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lumio" /></template>
