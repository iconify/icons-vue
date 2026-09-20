<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8amy6bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8amy6bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-eye" /></template>
