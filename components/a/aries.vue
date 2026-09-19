<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_52uqbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b_52uqbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:aries" /></template>
