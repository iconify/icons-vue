<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foflm7r3e.css';
import '../../css/t/tsj3hfbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="foflm7r3e"/><path class="tsj3hfbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coinmarketcap-blue" /></template>
