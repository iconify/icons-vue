<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze2kxtj6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze2kxtj6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-codesandbox-solid" /></template>
