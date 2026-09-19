<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4kxdbbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4kxdbbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cool" /></template>
