<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqb3qcc7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqb3qcc7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dot-02-s" /></template>
