<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a24b_-4jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a24b_-4jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-alt-light" /></template>
