<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea0pecbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea0pecbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:hardware-circuit" /></template>
