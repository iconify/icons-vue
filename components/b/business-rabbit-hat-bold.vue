<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha_mr3xlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha_mr3xlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:business-rabbit-hat-bold" /></template>
