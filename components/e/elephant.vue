<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytm83wbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytm83wbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:elephant" /></template>
