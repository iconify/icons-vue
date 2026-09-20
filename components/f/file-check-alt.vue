<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngtfjbbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngtfjbbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-check-alt" /></template>
