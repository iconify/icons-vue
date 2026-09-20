<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x29i4bbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x29i4bbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-bold" /></template>
