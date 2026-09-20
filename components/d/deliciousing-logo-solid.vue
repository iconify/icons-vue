<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh0s8cc3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jh0s8cc3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:deliciousing-logo-solid" /></template>
