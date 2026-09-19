<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pag-9sbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pag-9sbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crescent-staff" /></template>
