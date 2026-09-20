<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvne0-wkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvne0-wkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:anvil" /></template>
