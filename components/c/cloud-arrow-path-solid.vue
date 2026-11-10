<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpob04b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpob04b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-arrow-path-solid" /></template>
