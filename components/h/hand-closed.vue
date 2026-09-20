<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3d8ef5th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3d8ef5th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-closed" /></template>
