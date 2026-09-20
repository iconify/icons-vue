<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q47c6lywu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q47c6lywu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iconmoon-logo-solid" /></template>
