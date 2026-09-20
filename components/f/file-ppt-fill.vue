<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-jhqhb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-jhqhb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-ppt-fill" /></template>
