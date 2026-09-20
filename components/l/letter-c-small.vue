<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_1c3bbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_1c3bbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-c-small" /></template>
