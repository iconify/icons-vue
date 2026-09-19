<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b34y5p2yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b34y5p2yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:green-dragon-mahjong" /></template>
