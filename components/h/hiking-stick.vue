<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyr_xvayy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyr_xvayy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:hiking-stick" /></template>
