<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfsp98bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfsp98bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:histogram" /></template>
