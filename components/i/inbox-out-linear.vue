<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f-srkbcuc.css';
import '../../css/z/z0iqb0bhw.css';
import '../../css/d/dmfni0bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f-srkbcuc"/><path class="z0iqb0bhw"/><path class="dmfni0bso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-out-linear" /></template>
