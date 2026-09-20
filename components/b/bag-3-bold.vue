<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhl3owb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhl3owb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-3-bold" /></template>
