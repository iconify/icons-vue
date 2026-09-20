<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgr-qlbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgr-qlbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-number-0-filled" /></template>
