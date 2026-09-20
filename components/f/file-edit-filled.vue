<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2la8ubsr.css';
import '../../css/r/rphcwab-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2la8ubsr"/><path class="rphcwab-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-edit-filled" /></template>
