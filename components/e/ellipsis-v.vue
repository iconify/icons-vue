<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifwvrxeft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifwvrxeft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:ellipsis-v" /></template>
