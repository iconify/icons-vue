<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz1vefbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz1vefbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:crown" /></template>
