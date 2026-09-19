<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edz60ccaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="edz60ccaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-right-diamond-fill" /></template>
