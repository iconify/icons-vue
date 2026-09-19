<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkea-w76j.css';
import '../../css/u/u52trxfes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkea-w76j"/><path class="u52trxfes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:contacts-filled" /></template>
