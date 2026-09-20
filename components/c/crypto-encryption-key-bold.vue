<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oez_tozby.css';
import '../../css/y/y80r9ybqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oez_tozby"/><path class="y80r9ybqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:crypto-encryption-key-bold" /></template>
