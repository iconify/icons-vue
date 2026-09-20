<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf8cc9bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf8cc9bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ente" /></template>
