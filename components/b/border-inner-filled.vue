<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxo__5f1j.css';
import '../../css/u/uq4zqzbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxo__5f1j"/><path class="uq4zqzbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-inner-filled" /></template>
