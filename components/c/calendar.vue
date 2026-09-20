<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5489if1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b5489if1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:calendar" /></template>
