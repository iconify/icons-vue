<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj03jsb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj03jsb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-fill-24" /></template>
