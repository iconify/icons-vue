<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yybu3hn3z.css';
import '../../css/o/oa733acec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yybu3hn3z"/><path class="oa733acec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-to-line-bold" /></template>
