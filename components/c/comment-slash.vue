<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pda7mmfqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pda7mmfqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:comment-slash" /></template>
