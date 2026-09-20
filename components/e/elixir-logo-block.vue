<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjj1ddcwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjj1ddcwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elixir-logo-block" /></template>
