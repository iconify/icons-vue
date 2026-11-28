<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezqe3vhgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezqe3vhgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dumpling-solid" /></template>
