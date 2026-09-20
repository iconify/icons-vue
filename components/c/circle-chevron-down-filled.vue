<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cidwt8oom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cidwt8oom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-chevron-down-filled" /></template>
