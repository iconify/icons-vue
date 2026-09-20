<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp97wsb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rp97wsb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chef-hat-heart" /></template>
