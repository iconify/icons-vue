<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hisfu9s-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hisfu9s-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:corner-right-down" /></template>
