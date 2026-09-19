<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi8ylqbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":502};
const content = `<path class="bi8ylqbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:3ds-max" /></template>
