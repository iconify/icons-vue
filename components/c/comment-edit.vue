<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukc__5m7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukc__5m7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-edit" /></template>
