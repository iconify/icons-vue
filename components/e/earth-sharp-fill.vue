<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y06pqtqzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y06pqtqzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earth-sharp-fill" /></template>
