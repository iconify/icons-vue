<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6242fb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6242fb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-new" /></template>
