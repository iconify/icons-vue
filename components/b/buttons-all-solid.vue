<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfoen36tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfoen36tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:buttons-all-solid" /></template>
