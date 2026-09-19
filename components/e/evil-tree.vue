<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ash3_cbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ash3_cbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-tree" /></template>
