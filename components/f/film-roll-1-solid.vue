<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peddjfbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="peddjfbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:film-roll-1-solid" /></template>
