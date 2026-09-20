<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq0lnlb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-3};
const content = `<path class="bq0lnlb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:beer-f" /></template>
