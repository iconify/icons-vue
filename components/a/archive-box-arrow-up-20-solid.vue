<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdh_kmmdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fdh_kmmdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:archive-box-arrow-up-20-solid" /></template>
