<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by92ajukm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by92ajukm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flashlight-filled" /></template>
