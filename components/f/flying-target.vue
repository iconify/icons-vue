<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovw2lp1zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ovw2lp1zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flying-target" /></template>
