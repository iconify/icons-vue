<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vms0ktmkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vms0ktmkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:balance-line" /></template>
