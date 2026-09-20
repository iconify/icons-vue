<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lphdqt_3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lphdqt_3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magic-stick-2-outline" /></template>
