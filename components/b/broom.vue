<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzx2p7ngo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzx2p7ngo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:broom" /></template>
