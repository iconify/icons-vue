<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwypuebih.css';
import '../../css/c/cxt3jkwxn.css';
import '../../css/v/vhlyezb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwypuebih"/><path class="cxt3jkwxn"/><g><path class="vhlyezb4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-create" /></template>
