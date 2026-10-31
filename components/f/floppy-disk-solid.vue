<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knhprabbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="knhprabbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:floppy-disk-solid" /></template>
