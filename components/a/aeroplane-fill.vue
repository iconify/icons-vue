<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fljd5rbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fljd5rbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:aeroplane-fill" /></template>
