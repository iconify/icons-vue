<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in7ea2hci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in7ea2hci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-outline" /></template>
