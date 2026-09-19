<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhssn9pid.css';
import '../../css/i/iu35e1xme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhssn9pid"/><circle class="iu35e1xme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:bitaxe-filled" /></template>
