<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tci_6ibss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tci_6ibss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:album" /></template>
