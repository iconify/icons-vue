<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w19wmsbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w19wmsbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-share-alt" /></template>
