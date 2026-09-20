<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd-ve4bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd-ve4bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dns" /></template>
