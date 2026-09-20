<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kog5zicjb.css';
import '../../css/y/y02bymb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="kog5zicjb"/><path class="y02bymb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:commento" /></template>
