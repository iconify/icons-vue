<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asoryimij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asoryimij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:folder-delete" /></template>
