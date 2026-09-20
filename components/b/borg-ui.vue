<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb4fn93xo.css';
import '../../css/u/u82ou6akr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="wb4fn93xo"/><path class="u82ou6akr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:borg-ui" /></template>
