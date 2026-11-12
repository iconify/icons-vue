<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kog5zicjb.css';
import '../../css/q/q3ko5nmxb.css';
import '../../css/o/o06rrkwts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="kog5zicjb"/><path class="q3ko5nmxb"/><path class="o06rrkwts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:commento" /></template>
