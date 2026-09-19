<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-sap6zpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-sap6zpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bolt-bomb" /></template>
