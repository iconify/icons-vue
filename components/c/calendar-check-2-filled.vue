<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz9b-3b4c.css';
import '../../css/f/fh-ustbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz9b-3b4c"/><path class="fh-ustbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-check-2-filled" /></template>
