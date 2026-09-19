<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8iepnbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8iepnbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-empty-01" /></template>
