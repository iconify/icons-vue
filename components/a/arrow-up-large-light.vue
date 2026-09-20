<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb2nzco-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb2nzco-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-up-large-light" /></template>
