<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjo0s3sqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjo0s3sqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-g-filled" /></template>
