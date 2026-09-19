<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtx179f9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtx179f9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:heading3-outline" /></template>
