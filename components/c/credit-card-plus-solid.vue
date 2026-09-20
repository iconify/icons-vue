<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2wt_3bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2wt_3bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:credit-card-plus-solid" /></template>
