<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk58z1bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nk58z1bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-down-circle-solid" /></template>
