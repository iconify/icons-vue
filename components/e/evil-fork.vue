<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdntsb80a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdntsb80a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-fork" /></template>
