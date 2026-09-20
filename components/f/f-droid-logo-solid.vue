<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw787dblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lw787dblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:f-droid-logo-solid" /></template>
