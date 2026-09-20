<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3kxumt3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3kxumt3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-tie-hat" /></template>
