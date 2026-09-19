<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y01e7fbft.css';
import '../../css/j/jso3jy2en.css';
import '../../css/s/sve582cmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y01e7fbft"/><path class="jso3jy2en"/><path class="sve582cmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-text-twotone" /></template>
