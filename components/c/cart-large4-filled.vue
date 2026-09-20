<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2o3pdbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g2o3pdbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-large4-filled" /></template>
