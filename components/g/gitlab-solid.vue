<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch_g7mgvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch_g7mgvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:gitlab-solid" /></template>
