<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw5qyibzg.css';
import '../../css/j/jfyntqbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw5qyibzg"/><path class="jfyntqbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:heart-crack" /></template>
