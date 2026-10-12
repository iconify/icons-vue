<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmvzalb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmvzalb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-sync-filled" /></template>
