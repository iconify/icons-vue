<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9r6e7sfq.css';
import '../../css/c/c7rjmslqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9r6e7sfq"/><path clip-rule="evenodd" class="c7rjmslqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:drag-squares-vertical-duotone" /></template>
