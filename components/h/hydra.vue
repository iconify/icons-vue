<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmci_qb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmci_qb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hydra" /></template>
