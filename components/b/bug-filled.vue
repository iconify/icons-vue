<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_xeicb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_xeicb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bug-filled" /></template>
