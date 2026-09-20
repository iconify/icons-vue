<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wablnj0pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wablnj0pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-3-solid" /></template>
