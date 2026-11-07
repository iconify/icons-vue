<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3h3pubhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3h3pubhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-5-bold" /></template>
