<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr5u3zcnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr5u3zcnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-right-solid" /></template>
