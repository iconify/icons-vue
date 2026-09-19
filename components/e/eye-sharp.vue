<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shexgfo6g.css';
import '../../css/w/wsjn089ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="shexgfo6g"/><path class="wsjn089ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:eye-sharp" /></template>
