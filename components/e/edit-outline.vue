<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrac4jb6o.css';
import '../../css/l/lbx2im02e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrac4jb6o"/><path class="lbx2im02e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:edit-outline" /></template>
