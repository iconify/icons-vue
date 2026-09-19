<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_8ll006d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_8ll006d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chatbox-working" /></template>
