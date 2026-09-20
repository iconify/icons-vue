<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi5iun1qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi5iun1qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:junipernetworks" /></template>
