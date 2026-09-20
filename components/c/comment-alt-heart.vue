<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6oc-wo6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6oc-wo6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-heart" /></template>
