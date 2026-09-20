<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amaa57bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amaa57bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gas-station-filled" /></template>
