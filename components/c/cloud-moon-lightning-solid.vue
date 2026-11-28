<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kofy-7b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kofy-7b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-moon-lightning-solid" /></template>
