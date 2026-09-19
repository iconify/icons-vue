<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifbcutufq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ifbcutufq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:light-bulb" /></template>
