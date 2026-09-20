<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0ykkmgrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0ykkmgrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-narrow-wide" /></template>
