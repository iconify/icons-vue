<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4stqw62u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4stqw62u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-down-e" /></template>
