<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqg6um-gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqg6um-gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:file" /></template>
