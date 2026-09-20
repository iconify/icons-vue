<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2oh0-v6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2oh0-v6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-down-outline" /></template>
