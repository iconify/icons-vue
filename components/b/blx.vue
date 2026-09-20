<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stcw4r39t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stcw4r39t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:blx" /></template>
