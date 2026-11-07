<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7d917_2k.css';
import '../../css/u/ud-yki_gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l7d917_2k"/><path class="ud-yki_gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-minimalistic-2-bold" /></template>
