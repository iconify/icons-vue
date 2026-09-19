<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtavrv3rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gtavrv3rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:location-north" /></template>
