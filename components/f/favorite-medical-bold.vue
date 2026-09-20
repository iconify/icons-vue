<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwol1kcru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwol1kcru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:favorite-medical-bold" /></template>
