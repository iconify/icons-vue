<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7j41jzfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7j41jzfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:camera-fill" /></template>
