<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2od1mbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2od1mbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-s-solid" /></template>
