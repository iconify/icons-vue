<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxvidxbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="rxvidxbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:id-badge" /></template>
