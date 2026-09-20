<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx-2w7bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx-2w7bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dots-square-fill" /></template>
