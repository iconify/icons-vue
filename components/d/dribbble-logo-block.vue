<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ril0c-ubp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ril0c-ubp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dribbble-logo-block" /></template>
