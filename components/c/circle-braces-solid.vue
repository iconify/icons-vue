<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_26nbbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_26nbbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-braces-solid" /></template>
