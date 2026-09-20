<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgobatyfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="xgobatyfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:heliport-11" /></template>
