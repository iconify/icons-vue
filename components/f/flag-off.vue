<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tst2p8buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tst2p8buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flag-off" /></template>
