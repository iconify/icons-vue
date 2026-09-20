<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecwynrb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecwynrb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:authy-logo-solid" /></template>
