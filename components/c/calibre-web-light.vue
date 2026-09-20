<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we8ztxbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="we8ztxbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calibre-web-light" /></template>
