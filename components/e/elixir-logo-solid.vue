<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_z9o5mag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_z9o5mag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elixir-logo-solid" /></template>
