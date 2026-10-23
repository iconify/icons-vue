<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of8i30bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of8i30bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:columns-3" /></template>
