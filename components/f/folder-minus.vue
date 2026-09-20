<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw-p7j4rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-p7j4rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-minus" /></template>
