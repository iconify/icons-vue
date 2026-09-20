<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/r/ryk8grbre.css';
import '../../css/m/mh3bxnbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ryk8grbre"/><path class="mh3bxnbwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:divide" /></template>
