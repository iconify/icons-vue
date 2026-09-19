<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4bws3b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4bws3b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:bulb-fill" /></template>
