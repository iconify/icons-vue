<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z05v8zbft.css';
import '../../css/h/hpvm9bcft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z05v8zbft"/><path class="hpvm9bcft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cr-nmaster-dark" /></template>
