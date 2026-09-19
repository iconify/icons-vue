<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiyajtbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":961};
const content = `<path class="uiyajtbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fullstar" /></template>
