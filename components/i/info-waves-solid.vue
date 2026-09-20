<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytcyk_xzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytcyk_xzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:info-waves-solid" /></template>
