<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw0_fkb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pw0_fkb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cube" /></template>
