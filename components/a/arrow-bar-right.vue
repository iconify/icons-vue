<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5wf4rbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5wf4rbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-right" /></template>
