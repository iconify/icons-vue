<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls0nq9h6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ls0nq9h6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:anchor-solid" /></template>
