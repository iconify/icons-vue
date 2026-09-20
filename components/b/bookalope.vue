<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn_l_dbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn_l_dbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bookalope" /></template>
