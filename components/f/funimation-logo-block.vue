<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b03i_1hqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b03i_1hqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:funimation-logo-block" /></template>
