<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb24vccle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="nb24vccle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hotdog" /></template>
