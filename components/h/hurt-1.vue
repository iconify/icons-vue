<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkfyo6bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dkfyo6bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:hurt-1" /></template>
