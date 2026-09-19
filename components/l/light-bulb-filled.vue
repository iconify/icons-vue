<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx1zgacyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx1zgacyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:light-bulb-filled" /></template>
