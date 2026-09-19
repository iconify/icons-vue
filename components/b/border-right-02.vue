<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbd7tvy7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbd7tvy7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-right-02" /></template>
