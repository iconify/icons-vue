<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7eieudmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7eieudmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:codeblocks" /></template>
