<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf1ibccow.css';
import '../../css/i/ikuuwzb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rf1ibccow"/><path class="ikuuwzb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:layers-sharp" /></template>
