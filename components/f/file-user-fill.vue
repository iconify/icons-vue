<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixc1-fb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixc1-fb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-user-fill" /></template>
