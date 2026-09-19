<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y03fodbhj.css';
import '../../css/z/z-rhwwb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y03fodbhj"/><path class="z-rhwwb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-upload" /></template>
