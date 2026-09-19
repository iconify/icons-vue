<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kugk6f76b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kugk6f76b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:install-to-drive" /></template>
