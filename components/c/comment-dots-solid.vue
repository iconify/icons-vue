<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa6k8cc-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa6k8cc-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:comment-dots-solid" /></template>
