<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vply4ib2u.css';
import '../../css/e/eea_i9bnw.css';
import '../../css/x/xz2rsdmzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vply4ib2u"/><path class="eea_i9bnw"/><path class="xz2rsdmzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitlab" /></template>
