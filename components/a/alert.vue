<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4tx97b7q.css';
import '../../css/x/x-ff3h11f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4tx97b7q"/><circle class="x-ff3h11f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:alert" /></template>
