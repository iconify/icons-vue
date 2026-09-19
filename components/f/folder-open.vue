<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd27j6w7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd27j6w7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-open" /></template>
