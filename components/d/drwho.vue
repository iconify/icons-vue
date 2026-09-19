<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yenxbdjsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":910,"height":1026};
const content = `<path class="yenxbdjsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:drwho" /></template>
