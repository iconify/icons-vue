<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4_6mbc_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4_6mbc_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:link-check" /></template>
