<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi0bfrkdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bi0bfrkdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:folder-remove" /></template>
