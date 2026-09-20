<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln1esl2up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln1esl2up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-fill" /></template>
