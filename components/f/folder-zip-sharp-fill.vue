<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0szax6bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w0szax6bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-zip-sharp-fill" /></template>
