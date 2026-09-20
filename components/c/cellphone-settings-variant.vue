<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vefdffbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vefdffbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-settings-variant" /></template>
