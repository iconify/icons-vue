<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj87vsbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj87vsbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-zip-sharp" /></template>
