<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erfmhctcc.css';
import '../../css/b/b-t5aibbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer erfmhctcc"/><path class="b-t5aibbb duoicon-secondary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:location" /></template>
