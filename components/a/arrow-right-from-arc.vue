<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlmkxu4at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlmkxu4at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right-from-arc" /></template>
