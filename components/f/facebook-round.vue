<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1szsdb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1szsdb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:facebook-round" /></template>
