<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txg_57bbj.css';
import '../../css/y/yz7fw7w9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="txg_57bbj"/><path class="yz7fw7w9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:luggage-48-bold" /></template>
