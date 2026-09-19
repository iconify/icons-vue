<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icn-0wbfj.css';
import '../../css/d/dnot0zbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icn-0wbfj"/><path class="dnot0zbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-search-filled" /></template>
