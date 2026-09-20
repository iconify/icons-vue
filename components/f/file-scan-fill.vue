<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1u6f3bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1u6f3bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-scan-fill" /></template>
