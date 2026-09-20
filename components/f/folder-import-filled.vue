<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhgf4oq2b.css';
import '../../css/l/lguu5_wzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhgf4oq2b"/><path class="lguu5_wzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-import-filled" /></template>
