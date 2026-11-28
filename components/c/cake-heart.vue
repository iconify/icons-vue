<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bufslqklq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bufslqklq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cake-heart" /></template>
