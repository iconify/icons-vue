<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvj3041mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nvj3041mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:eightball" /></template>
