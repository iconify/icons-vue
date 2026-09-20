<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyubx5bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyubx5bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-solid" /></template>
