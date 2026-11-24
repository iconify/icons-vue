<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um7_4ac7p.css';
import '../../css/k/kfueumbyk.css';
import '../../css/p/p98w-ymbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="um7_4ac7p"/><rect class="kfueumbyk"/><path class="p98w-ymbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:besucherlogin" /></template>
