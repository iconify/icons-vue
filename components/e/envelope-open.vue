<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqx-qbbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqx-qbbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:envelope-open" /></template>
