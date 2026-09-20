<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8c4lps6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8c4lps6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lamp-fill" /></template>
