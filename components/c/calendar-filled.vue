<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puzsmobar.css';
import '../../css/n/npj2p4b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puzsmobar"/><path clip-rule="evenodd" class="npj2p4b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:calendar-filled" /></template>
