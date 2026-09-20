<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t85k80b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t85k80b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:comedy-mask-and-tragedy-mask" /></template>
