<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt9tg9b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt9tg9b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-text-sharp-fill" /></template>
