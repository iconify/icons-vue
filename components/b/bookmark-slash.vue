<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssl67mbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssl67mbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bookmark-slash" /></template>
