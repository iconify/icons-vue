<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxy8o6b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxy8o6b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-pray-filled" /></template>
