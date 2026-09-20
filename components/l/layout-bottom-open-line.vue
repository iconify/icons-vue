<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxfrmfydy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxfrmfydy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-bottom-open-line" /></template>
