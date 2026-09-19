<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt4-40r2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bt4-40r2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:backward-step" /></template>
