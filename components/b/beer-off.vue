<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu_edqbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu_edqbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:beer-off" /></template>
