<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m42zp2umy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="m42zp2umy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gameboy" /></template>
