<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3h0_zb2o.css';
import '../../css/n/n3pz-6bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3h0_zb2o"/><path class="n3pz-6bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-minimalistic-bold" /></template>
