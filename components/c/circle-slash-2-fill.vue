<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwlylg9wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwlylg9wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-slash-2-fill" /></template>
