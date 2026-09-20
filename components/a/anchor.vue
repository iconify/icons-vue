<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo4oxpv7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vo4oxpv7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:anchor" /></template>
