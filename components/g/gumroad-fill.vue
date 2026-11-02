<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm5l7hf7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5l7hf7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gumroad-fill" /></template>
