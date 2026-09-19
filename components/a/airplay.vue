<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp1oxqb9n.css';
import '../../css/r/rr6qynbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sp1oxqb9n"/><path class="rr6qynbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:airplay" /></template>
