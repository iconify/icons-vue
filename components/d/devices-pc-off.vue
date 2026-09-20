<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu8vh-i6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu8vh-i6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:devices-pc-off" /></template>
