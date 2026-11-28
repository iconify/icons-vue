<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2y9x-b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f2y9x-b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-open-pitched-building-with-double-z-door" /></template>
