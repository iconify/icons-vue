<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_eg9t9sm.css';
import '../../css/b/bpcfxvb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_eg9t9sm"/><path class="bpcfxvb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grimoire-ttrpg" /></template>
