<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmfmgycje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmfmgycje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fandom-logo-1" /></template>
