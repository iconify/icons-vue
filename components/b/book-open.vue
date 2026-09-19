<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edtsal6eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edtsal6eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-open" /></template>
