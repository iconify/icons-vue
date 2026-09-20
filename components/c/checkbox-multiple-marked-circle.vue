<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nskwcxbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nskwcxbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-multiple-marked-circle" /></template>
