<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7wvp7oxw.css';
import '../../css/s/s4dgi_7mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7wvp7oxw"/><path class="s4dgi_7mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-x-2-filled" /></template>
