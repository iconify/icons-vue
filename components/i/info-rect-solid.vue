<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/masq27b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="masq27b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:info-rect-solid" /></template>
