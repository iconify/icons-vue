<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sws_sk_no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sws_sk_no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-tray-solid" /></template>
