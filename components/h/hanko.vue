<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddtzh172g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ddtzh172g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hanko" /></template>
