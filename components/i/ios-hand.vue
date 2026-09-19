<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz6ec88-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zz6ec88-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-hand" /></template>
