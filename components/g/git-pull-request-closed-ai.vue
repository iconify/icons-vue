<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lavxv1b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lavxv1b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:git-pull-request-closed-ai" /></template>
