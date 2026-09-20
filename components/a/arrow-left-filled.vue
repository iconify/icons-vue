<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm2p3jkwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm2p3jkwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left-filled" /></template>
