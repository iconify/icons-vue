<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymy8u3fmy.css';
import '../../css/d/di3cg09op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymy8u3fmy"/><path class="di3cg09op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:analyze-filled" /></template>
