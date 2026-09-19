<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9jk3binf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9jk3binf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-word" /></template>
