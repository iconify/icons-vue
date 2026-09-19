<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qakp8vbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qakp8vbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:buoy-filled" /></template>
