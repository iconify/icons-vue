<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0bk5fh_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0bk5fh_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up" /></template>
