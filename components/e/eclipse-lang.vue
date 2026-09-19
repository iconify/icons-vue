<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqbxe7b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqbxe7b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:eclipse-lang" /></template>
