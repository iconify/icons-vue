<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjb7ndb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjb7ndb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-git-2-fill" /></template>
