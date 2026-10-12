<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgjuh8b2j.css';
import '../../css/z/zqpq1rb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgjuh8b2j"/><path class="zqpq1rb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:feather-filled" /></template>
