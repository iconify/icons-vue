<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg3jbr79j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fg3jbr79j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:light-bulb-off-16" /></template>
