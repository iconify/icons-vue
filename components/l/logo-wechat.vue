<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj3gltbbh.css';
import '../../css/g/gvjt3ybox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cj3gltbbh"/><path class="gvjt3ybox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-wechat" /></template>
