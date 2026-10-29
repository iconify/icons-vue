<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl8f_3bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl8f_3bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bread-solid" /></template>
