<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpnw-rbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpnw-rbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:align-center" /></template>
