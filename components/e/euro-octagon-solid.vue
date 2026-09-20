<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvlm1bbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvlm1bbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:euro-octagon-solid" /></template>
