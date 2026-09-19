<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn9-9y8lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn9-9y8lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:asterisk" /></template>
