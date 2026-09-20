<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzs07zk9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzs07zk9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-download-fill" /></template>
