<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdzgxo04f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdzgxo04f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-zip-fill" /></template>
