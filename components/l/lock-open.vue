<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keb02lb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keb02lb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:lock-open" /></template>
