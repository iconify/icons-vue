<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgn5slbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgn5slbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:chevron-up" /></template>
