<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvw6idboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvw6idboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:check-light" /></template>
