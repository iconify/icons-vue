<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/effjgp2eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="effjgp2eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:board-subway" /></template>
