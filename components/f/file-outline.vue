<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz01z324w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz01z324w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-outline" /></template>
