<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_r5o2bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_r5o2bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lock-open-password-solid" /></template>
