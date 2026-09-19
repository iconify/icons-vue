<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk58vecrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk58vecrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ban" /></template>
