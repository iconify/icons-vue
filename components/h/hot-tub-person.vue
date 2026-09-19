<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmiwrrb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmiwrrb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hot-tub-person" /></template>
