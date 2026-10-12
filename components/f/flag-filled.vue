<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae-x9bbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae-x9bbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flag-filled" /></template>
