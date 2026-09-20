<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7gcfmb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l7gcfmb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-bold" /></template>
