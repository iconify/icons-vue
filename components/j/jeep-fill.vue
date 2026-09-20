<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgd-5o5ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgd-5o5ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:jeep-fill" /></template>
