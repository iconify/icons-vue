<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnr_e_b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnr_e_b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-outgoing-01" /></template>
