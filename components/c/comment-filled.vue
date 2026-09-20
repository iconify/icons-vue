<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evo6idb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evo6idb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:comment-filled" /></template>
