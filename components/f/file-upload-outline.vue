<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjwem2boo.css';
import '../../css/h/hjgunfmzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jjwem2boo"/><path class="hjgunfmzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:file-upload-outline" /></template>
