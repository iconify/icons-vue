<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwa2tab4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xwa2tab4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-bold" /></template>
