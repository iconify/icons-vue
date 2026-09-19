<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqqpylhzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqqpylhzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:dialpad-solid" /></template>
