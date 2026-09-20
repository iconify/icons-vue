<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fus1u3bvc.css';
import '../../css/m/m-g2ynbrd.css';
import '../../css/t/tvdh9jgjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fus1u3bvc"/><path class="m-g2ynbrd"/><path class="tvdh9jgjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-manager" /></template>
