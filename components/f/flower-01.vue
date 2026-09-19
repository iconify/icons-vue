<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m0lddebws.css';
import '../../css/t/tox0_487f.css';
import '../../css/w/w-urnk1wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m0lddebws"/><path clip-rule="evenodd" class="tox0_487f"/><path class="w-urnk1wg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flower-01" /></template>
