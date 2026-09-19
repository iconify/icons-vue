<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8tk3xbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8tk3xbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:down-left-and-up-right-to-center" /></template>
