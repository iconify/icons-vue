<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3anqz2df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3anqz2df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:leaf-filled" /></template>
