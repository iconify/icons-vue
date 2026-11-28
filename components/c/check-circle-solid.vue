<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t__uj6bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t__uj6bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:check-circle-solid" /></template>
