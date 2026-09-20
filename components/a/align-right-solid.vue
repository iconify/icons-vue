<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayhvrwn1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayhvrwn1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:align-right-solid" /></template>
