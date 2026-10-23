<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b901epbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b901epbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bone-fracture" /></template>
