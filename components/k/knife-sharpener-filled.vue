<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuvx7sbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iuvx7sbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:knife-sharpener-filled" /></template>
