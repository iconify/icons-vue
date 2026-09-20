<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcl4v3bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tcl4v3bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:convos-light" /></template>
