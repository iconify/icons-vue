<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abl8a-bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abl8a-bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-plus-sharp" /></template>
