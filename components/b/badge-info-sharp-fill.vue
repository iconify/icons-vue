<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw2l8obpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw2l8obpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-info-sharp-fill" /></template>
