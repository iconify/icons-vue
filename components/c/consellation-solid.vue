<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv5w7ebwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fv5w7ebwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:consellation-solid" /></template>
