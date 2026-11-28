<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcqb7divy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcqb7divy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-zip-check" /></template>
