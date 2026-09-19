<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xree5zkbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xree5zkbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-office-solid" /></template>
