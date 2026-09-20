<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb_adqbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xb_adqbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:keyboard-wireless-2" /></template>
