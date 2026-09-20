<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a446ljbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a446ljbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:drag-squares-horizontal" /></template>
