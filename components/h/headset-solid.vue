<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_hrzfb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_hrzfb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headset-solid" /></template>
