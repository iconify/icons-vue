<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7322fblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b7322fblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-check-16-solid" /></template>
