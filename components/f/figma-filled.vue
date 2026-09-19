<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp1639kxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp1639kxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:figma-filled" /></template>
