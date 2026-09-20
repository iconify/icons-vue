<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbfdil6ak.css';
import '../../css/q/qvfvdgulf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbfdil6ak"/><path class="qvfvdgulf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kroma" /></template>
