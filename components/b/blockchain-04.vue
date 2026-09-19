<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve37pubxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve37pubxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:blockchain-04" /></template>
