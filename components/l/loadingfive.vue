<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppu21twmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ppu21twmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingfive" /></template>
