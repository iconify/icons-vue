<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2dnkcbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2dnkcbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-flask" /></template>
