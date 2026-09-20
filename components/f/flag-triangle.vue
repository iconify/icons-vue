<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5_so861b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5_so861b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-triangle" /></template>
