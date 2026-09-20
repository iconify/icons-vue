<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh_k-lb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh_k-lb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:layers-fill" /></template>
