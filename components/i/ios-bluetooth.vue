<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu3__vpyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cu3__vpyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bluetooth" /></template>
