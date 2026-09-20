<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yno1lhbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yno1lhbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-wix" /></template>
