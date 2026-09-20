<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgq-hoi-s.css';
import '../../css/b/bqo7skq6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgq-hoi-s"/><path class="bqo7skq6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-search-filled" /></template>
