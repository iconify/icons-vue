<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0g43yble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0g43yble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-yen-solid" /></template>
