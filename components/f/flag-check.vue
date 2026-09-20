<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvntf3bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvntf3bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-check" /></template>
