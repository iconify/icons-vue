<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us0mlcc8v.css';
import '../../css/m/mb6i43i-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="us0mlcc8v"/><path class="mb6i43i-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-refresh" /></template>
