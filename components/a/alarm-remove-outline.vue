<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il8m2xbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il8m2xbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-remove-outline" /></template>
