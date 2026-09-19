<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb-4b9ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb-4b9ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:key-command" /></template>
