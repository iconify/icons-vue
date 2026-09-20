<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzocm9dtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pzocm9dtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:child-solid" /></template>
