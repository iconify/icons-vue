<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2skmjbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":448};
const content = `<path class="g2skmjbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:krop" /></template>
