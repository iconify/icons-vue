<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdxc7ob4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdxc7ob4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fitbit-logo" /></template>
