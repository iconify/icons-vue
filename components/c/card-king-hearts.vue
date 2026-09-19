<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4hztjbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4hztjbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-king-hearts" /></template>
