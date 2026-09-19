<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsm3uwb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsm3uwb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:block" /></template>
