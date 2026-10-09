<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxj-1cpyy.css';
import '../../css/b/bhq-_uklw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hxj-1cpyy"/><path class="bhq-_uklw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:a-frame-20-bold" /></template>
