<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpg89sb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gpg89sb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-2-bold" /></template>
