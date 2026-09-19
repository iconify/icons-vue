<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrl1jkw7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrl1jkw7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-fastforward-outline" /></template>
