<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4q-79nri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r4q-79nri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:linux-mint-logo-2-solid" /></template>
