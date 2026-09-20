<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c14g8kbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c14g8kbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:leaf-outline" /></template>
