<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwtip4izv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwtip4izv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-m-circle-solid" /></template>
