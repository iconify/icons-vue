<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03svacbz.css';
import '../../css/j/jwf99rbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s03svacbz"/><path class="jwf99rbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-icon-filled" /></template>
