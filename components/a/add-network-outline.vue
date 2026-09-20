<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-7suk1ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-7suk1ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-network-outline" /></template>
