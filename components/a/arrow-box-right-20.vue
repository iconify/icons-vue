<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlb3uob7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tlb3uob7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-box-right-20" /></template>
