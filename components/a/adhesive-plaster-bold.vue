<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io95umbud.css';
import '../../css/v/vr0cnhd_c.css';
import '../../css/d/dc6a51hpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io95umbud"/><path clip-rule="evenodd" class="vr0cnhd_c"/><path class="dc6a51hpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:adhesive-plaster-bold" /></template>
