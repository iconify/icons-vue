<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6m6l-blr.css';
import '../../css/a/add8fqwim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6m6l-blr"/><path class="add8fqwim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-light" /></template>
