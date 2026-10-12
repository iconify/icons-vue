<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_-lavb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_-lavb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dice-5-filled" /></template>
