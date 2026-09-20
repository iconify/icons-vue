<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py9j02b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py9j02b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ban" /></template>
