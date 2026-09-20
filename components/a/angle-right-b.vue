<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loowl_btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loowl_btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:angle-right-b" /></template>
