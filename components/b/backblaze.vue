<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn31dub8v.css';
import '../../css/c/ce504-bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn31dub8v"/><path class="ce504-bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:backblaze" /></template>
