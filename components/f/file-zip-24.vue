<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqg7_db4w.css';
import '../../css/f/frhmf7-sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqg7_db4w"/><path class="frhmf7-sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-zip-24" /></template>
