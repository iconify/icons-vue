<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur2nqhb_s.css';
import '../../css/c/cz512trdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ur2nqhb_s"/><path class="cz512trdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grimoire-ttrpg-dark" /></template>
