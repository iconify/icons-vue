<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_3-2pbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_3-2pbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:american-football-sharp" /></template>
