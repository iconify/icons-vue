<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni1j1zb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="ni1j1zb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:cancel" /></template>
