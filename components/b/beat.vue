<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpl-z2bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="zpl-z2bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:beat" /></template>
