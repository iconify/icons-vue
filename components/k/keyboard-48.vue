<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7olx61gw.css';
import '../../css/p/pru8skb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r7olx61gw"/><path class="pru8skb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:keyboard-48" /></template>
