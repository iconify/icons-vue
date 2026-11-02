<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd2oewbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd2oewbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fax-fill" /></template>
