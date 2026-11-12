<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etg9crbrk.css';
import '../../css/i/ipz9c_5nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etg9crbrk"/><path class="ipz9c_5nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:espconnect-dark" /></template>
