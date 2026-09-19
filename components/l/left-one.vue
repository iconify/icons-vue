<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m63m8hbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m63m8hbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:left-one" /></template>
