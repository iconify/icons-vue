<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olpd3zbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="olpd3zbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:justice-scale-2-solid" /></template>
