<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd5gzltfq.css';
import '../../css/x/x4h7aul0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd5gzltfq"/><path class="x4h7aul0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-dot-bold-duotone" /></template>
