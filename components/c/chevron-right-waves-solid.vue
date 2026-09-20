<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzgf_2bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzgf_2bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-right-waves-solid" /></template>
