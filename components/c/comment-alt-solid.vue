<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc1r45b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jc1r45b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:comment-alt-solid" /></template>
