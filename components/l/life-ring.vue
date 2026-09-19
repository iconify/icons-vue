<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq74e8-al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aq74e8-al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:life-ring" /></template>
