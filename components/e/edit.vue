<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bro3b7b7u.css';
import '../../css/p/ptu48kbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bro3b7b7u"/><path class="ptu48kbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:edit" /></template>
