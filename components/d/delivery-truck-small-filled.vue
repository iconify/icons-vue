<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da8z4_zfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="da8z4_zfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:delivery-truck-small-filled" /></template>
