<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptj_bibnz.css';
import '../../css/z/z37-xpb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ptj_bibnz"/><path class="z37-xpb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cog-outline" /></template>
