<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx26_9q9g.css';
import '../../css/f/fxj5wpbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx26_9q9g"/><path class="fxj5wpbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-bookmark-filled" /></template>
