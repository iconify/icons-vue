<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_tbe7bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_tbe7bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:imgur-logo-solid" /></template>
