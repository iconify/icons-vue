<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t98k1grdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t98k1grdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-x-mark-solid" /></template>
