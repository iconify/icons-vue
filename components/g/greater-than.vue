<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp035-4hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xp035-4hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:greater-than" /></template>
