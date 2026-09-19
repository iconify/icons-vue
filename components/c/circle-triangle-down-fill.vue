<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il7qhmbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il7qhmbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-triangle-down-fill" /></template>
