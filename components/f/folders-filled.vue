<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfn2hac5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfn2hac5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folders-filled" /></template>
