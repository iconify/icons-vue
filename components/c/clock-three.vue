<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixxqi91bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixxqi91bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:clock-three" /></template>
