<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5wad8b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5wad8b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperdx-light" /></template>
