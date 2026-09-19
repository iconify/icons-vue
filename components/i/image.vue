<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agku-_b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="agku-_b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:image" /></template>
