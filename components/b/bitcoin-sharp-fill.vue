<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xku04_bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xku04_bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bitcoin-sharp-fill" /></template>
