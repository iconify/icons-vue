<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5x_o2bjy.css';
import '../../css/z/zo1w86b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5x_o2bjy"/><path class="zo1w86b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inspircd" /></template>
