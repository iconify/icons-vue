<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0vgceb-l.css';
import '../../css/c/cnllsbb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0vgceb-l"/><path class="cnllsbb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:file-solid" /></template>
