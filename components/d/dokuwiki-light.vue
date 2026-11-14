<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcrvamb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcrvamb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dokuwiki-light" /></template>
