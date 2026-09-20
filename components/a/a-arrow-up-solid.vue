<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgoaobaxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgoaobaxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:a-arrow-up-solid" /></template>
