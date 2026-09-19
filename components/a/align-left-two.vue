<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nar4fkb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nar4fkb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-left-two" /></template>
