<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v18drh_jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v18drh_jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightbulb-outline" /></template>
