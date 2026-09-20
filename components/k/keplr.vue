<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2p0yrbfm.css';
import '../../css/c/cgy263brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2p0yrbfm"/><path clip-rule="evenodd" class="cgy263brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:keplr" /></template>
