<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz_854_cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary sz_854_cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:explosion-duotone" /></template>
