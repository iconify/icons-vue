<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ym7p8cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5ym7p8cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dental" /></template>
