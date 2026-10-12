<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgv34el5t.css';
import '../../css/n/nsl4o5b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fgv34el5t"/><path class="nsl4o5b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-generic-fill-20" /></template>
