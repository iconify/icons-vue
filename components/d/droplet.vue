<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgb63nblv.css';
import '../../css/b/btx5mjbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pgb63nblv"/><path class="btx5mjbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:droplet" /></template>
