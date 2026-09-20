<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v22vrs4cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v22vrs4cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:electronic-arts-logo-solid" /></template>
