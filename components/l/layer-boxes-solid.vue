<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9ceq2bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9ceq2bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layer-boxes-solid" /></template>
