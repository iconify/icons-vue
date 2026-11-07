<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6tzh5bbz.css';
import '../../css/x/xkrbx0bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6tzh5bbz"/><path class="xkrbx0bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:display-bold-duotone" /></template>
