<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eduva4b7t.css';
import '../../css/m/mnciwzbrt.css';
import '../../css/r/r79vqubxp.css';
import '../../css/s/sefx_kbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eduva4b7t"/><path class="mnciwzbrt"/><path class="r79vqubxp"/><path class="sefx_kbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-outline" /></template>
