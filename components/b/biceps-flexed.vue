<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3q8ujb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3q8ujb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:biceps-flexed" /></template>
