<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w38u07vkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w38u07vkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bear" /></template>
