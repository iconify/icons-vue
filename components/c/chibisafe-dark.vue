<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnm87zbsi.css';
import '../../css/j/jpb4tzbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnm87zbsi"/><path class="jpb4tzbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chibisafe-dark" /></template>
