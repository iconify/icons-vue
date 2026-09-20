<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-6_ylk_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-6_ylk_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-t" /></template>
