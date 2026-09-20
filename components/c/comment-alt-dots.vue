<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ondv263yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ondv263yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-dots" /></template>
