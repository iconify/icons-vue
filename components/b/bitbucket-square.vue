<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b568kobcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="b568kobcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bitbucket-square" /></template>
