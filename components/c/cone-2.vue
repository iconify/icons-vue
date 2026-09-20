<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9czzrh6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9czzrh6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cone-2" /></template>
