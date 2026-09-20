<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlqbijbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hlqbijbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:home-1-solid" /></template>
