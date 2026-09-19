<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg8-xqbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xg8-xqbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-grin-wink" /></template>
