<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7f-sx8dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7f-sx8dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inoreader" /></template>
