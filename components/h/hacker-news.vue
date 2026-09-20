<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a42oku2cl.css';
import '../../css/y/ytr1p0b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a42oku2cl"/><path class="ytr1p0b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hacker-news" /></template>
