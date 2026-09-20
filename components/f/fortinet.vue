<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emg_5vb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emg_5vb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fortinet" /></template>
