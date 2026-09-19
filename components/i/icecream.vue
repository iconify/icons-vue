<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv_0qibyt.css';
import '../../css/y/yi-zn1bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv_0qibyt"/><path class="yi-zn1bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:icecream" /></template>
