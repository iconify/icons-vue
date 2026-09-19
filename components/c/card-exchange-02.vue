<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3u21xbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3u21xbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:card-exchange-02" /></template>
