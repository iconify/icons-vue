<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s04b96bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s04b96bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-add" /></template>
