<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbd9pswha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbd9pswha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-exclamation" /></template>
