<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om1bhbc1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="om1bhbc1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:location-pin-store-solid" /></template>
