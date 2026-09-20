<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw74mcvdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tw74mcvdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aht" /></template>
