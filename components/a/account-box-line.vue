<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npvw37byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npvw37byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-box-line" /></template>
