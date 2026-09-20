<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg3k_nb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qg3k_nb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-5-solid" /></template>
