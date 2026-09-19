<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcje2ji1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcje2ji1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-merge" /></template>
