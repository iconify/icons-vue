<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kndqyzbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kndqyzbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-plus" /></template>
