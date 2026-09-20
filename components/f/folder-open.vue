<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br3drl69p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br3drl69p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-open" /></template>
