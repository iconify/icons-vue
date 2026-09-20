<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw99hzb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw99hzb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bell" /></template>
