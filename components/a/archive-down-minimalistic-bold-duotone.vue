<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke6bcb_hh.css';
import '../../css/k/k_ae5dbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke6bcb_hh"/><path clip-rule="evenodd" class="k_ae5dbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-minimalistic-bold-duotone" /></template>
