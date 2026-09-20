<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idnpn86mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idnpn86mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-down-left-sharp-fill" /></template>
